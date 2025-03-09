# Function: <code>security_inode_init_security</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582238720,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:366",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "mm/shmem.c:shmem_symlink",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238720,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457408,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:367",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457408,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582549872,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:376",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549872,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582635776,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:981",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635776,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582789584,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:930",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789584,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582989216,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:472",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989216,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583101152,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:993",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101152,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583286496,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1007",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286496,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583391840,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1047",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391840,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730368,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1195",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730368,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583850544,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1197",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850544,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875808,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1242",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875808,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584239984,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1242",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239984,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584846000,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1262",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846000,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585548304,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1260",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585548304,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585778928,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1756",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778928,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027072,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1811",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027072,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495142960,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1047",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495142960,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228530676,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1047",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228530676,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289061456,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1047",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289061456,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274392272,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1047",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274392272,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583360576,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1047",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360576,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583297680,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1047",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583297680,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583344352,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1047",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344352,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int security_inode_init_security(struct inode * inode, struct inode * dir, const struct qstr * qstr, const initxattrs initxattrs, void * fs_data)
```

```json
{
  "name": "security_inode_init_security",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583439536,
      "name": "security_inode_init_security",
      "external": true,
      "loc": "security/security.c:1047",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "fs/ext4/xattr_security.c:ext4_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439536,
      "name": "security_inode_init_security",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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

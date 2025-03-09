# Function: <code>securityfs_create_symlink</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653216,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:254",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653216,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582808352,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:254",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808352,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002448,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:254",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002448,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583115776,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:255",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115776,
      "name": "securityfs_create_symlink",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583302720,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302720,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407376,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407376,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583747984,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747984,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868128,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868128,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583894288,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894288,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258112,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258112,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584870480,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870480,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585575984,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585575984,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585807248,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807248,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586055664,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055664,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495161440,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495161440,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228548664,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228548664,
      "name": "securityfs_create_symlink",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289096752,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289096752,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274406276,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274406276,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583376112,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376112,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583313216,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313216,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583359888,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583359888,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583455072,
      "name": "securityfs_create_symlink",
      "external": true,
      "loc": "security/inode.c:260",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583455072,
      "name": "securityfs_create_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct dentry * securityfs_create_symlink(const char * name, struct dentry * parent, const char * target, const struct inode_operations * iops)
```
</details>
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

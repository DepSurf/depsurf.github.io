# Function: <code>__vfs_removexattr</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391120,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:370",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391120,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446448,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:370",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446448,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588416,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:371",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588416,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745776,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745776,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832304,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:368",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832304,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956608,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956608,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029312,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029312,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582264080,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:406",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264080,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313792,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:444",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313792,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int __vfs_removexattr(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582341424,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:458",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341424,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int __vfs_removexattr(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661968,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:459",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661968,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int __vfs_removexattr(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583202192,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:460",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202192,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __vfs_removexattr(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780768,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:484",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780768,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int __vfs_removexattr(struct mnt_idmap * idmap, struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583997456,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:505",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997456,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int __vfs_removexattr(struct mnt_idmap * idmap, struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584210096,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:505",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210096,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493553552,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493553552,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227102380,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227102380,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287124880,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287124880,
      "name": "__vfs_removexattr",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273213950,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273213950,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581998048,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998048,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935616,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935616,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989328,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989328,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int __vfs_removexattr(struct dentry * dentry, const char * name)
```

```json
{
  "name": "__vfs_removexattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059792,
      "name": "__vfs_removexattr",
      "external": true,
      "loc": "fs/xattr.c:369",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_killpriv",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059792,
      "name": "__vfs_removexattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __vfs_removexattr(struct dentry * dentry, const char * name)
```
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, name</code> ➡️ <code>mnt_userns, dentry, name</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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

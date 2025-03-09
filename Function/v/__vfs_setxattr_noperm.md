# Function: <code>__vfs_setxattr_noperm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149344,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:92",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149344,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581315168,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:99",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581315168,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581394432,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:169",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581394432,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449712,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:169",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449712,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591696,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591696,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581750528,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750528,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837056,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:169",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837056,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581961424,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961424,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582034176,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034176,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582267648,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_locked",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267648,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316880,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:197",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_locked",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316880,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int __vfs_setxattr_noperm(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344320,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:202",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_locked",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_fix_xattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344320,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int __vfs_setxattr_noperm(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665136,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:202",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_locked",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_fix_xattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665136,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
int __vfs_setxattr_noperm(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583207008,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:204",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_locked",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_fix_xattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583207008,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int __vfs_setxattr_noperm(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583781472,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:224",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_locked",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_fix_xattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583781472,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int __vfs_setxattr_noperm(struct mnt_idmap * idmap, struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000672,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:223",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_locked",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_fix_xattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000672,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int __vfs_setxattr_noperm(struct mnt_idmap * idmap, struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584213312,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:223",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_locked",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_fix_xattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213312,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493558744,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493558744,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227105780,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_fix_xattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227105780,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287131808,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_fix_xattr",
        "security/integrity/ima/ima_appraise.c:ima_fix_xattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287131808,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273216910,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/ima/ima_appraise.c:ima_fix_xattr",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273216910,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002912,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002912,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940480,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940480,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994192,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994192,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int __vfs_setxattr_noperm(struct dentry * dentry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr_noperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064656,
      "name": "__vfs_setxattr_noperm",
      "external": true,
      "loc": "fs/xattr.c:170",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "security/selinux/hooks.c:selinux_inode_setsecctx",
        "security/smack/smack_lsm.c:smack_inode_setsecctx",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064656,
      "name": "__vfs_setxattr_noperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, name, value, size, flags</code> ➡️ <code>mnt_userns, dentry, name, value, size, flags</code>
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

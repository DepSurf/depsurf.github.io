# Function: <code>vfs_getxattr_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146928,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:181",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_xattr_cmp",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146928,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312080,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:189",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312080,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391696,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391696,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581447024,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581447024,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588976,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:269",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588976,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581746192,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746192,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832720,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:267",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832720,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581957008,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581957008,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029712,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029712,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582264480,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:305",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:find_attach",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264480,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582314416,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:343",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:find_attach",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582314416,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t vfs_getxattr_alloc(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349248,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:355",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:find_attach",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349248,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
ssize_t vfs_getxattr_alloc(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582662624,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:355",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:find_attach",
        "security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_xattr_change",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582662624,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
ssize_t vfs_getxattr_alloc(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583208208,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:357",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:find_attach",
        "security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_xattr_change",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583208208,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int vfs_getxattr_alloc(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583785584,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:378",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:find_attach",
        "security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785584,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int vfs_getxattr_alloc(struct mnt_idmap * idmap, struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001920,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:376",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:find_attach",
        "security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001920,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int vfs_getxattr_alloc(struct mnt_idmap * idmap, struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584214560,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:376",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:find_attach",
        "security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214560,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493554008,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493554008,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227102820,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227102820,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287125952,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287125952,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273214364,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273214364,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581998448,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998448,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936016,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936016,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989728,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989728,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t vfs_getxattr_alloc(struct dentry * dentry, const char * name, char * * xattr_value, size_t xattr_size, gfp_t flags)
```

```json
{
  "name": "vfs_getxattr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582060192,
      "name": "vfs_getxattr_alloc",
      "external": true,
      "loc": "fs/xattr.c:268",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/integrity/ima/ima_appraise.c:ima_read_xattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_crypto.c:evm_update_evmxattr",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582060192,
      "name": "vfs_getxattr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
<code>dentry, name, xattr_value, xattr_size, flags</code> ➡️ <code>mnt_userns, dentry, name, xattr_value, xattr_size, flags</code>
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
<b>Return type changed. </b>
<code>ssize_t</code> ➡️ <code>int</code>
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

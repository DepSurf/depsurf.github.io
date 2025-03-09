# Function: <code>__vfs_getxattr</code>

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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391008,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391008,
      "name": "__vfs_getxattr",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446336,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446336,
      "name": "__vfs_getxattr",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588288,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:304",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588288,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745648,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745648,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832176,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:302",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832176,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956480,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956480,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029184,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029184,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582268902,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:340",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263952,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582318934,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:378",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313664,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582346415,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:390",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341296,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582668655,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:391",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_read_protected_xattrs",
        "security/integrity/evm/evm_main.c:evm_read_protected_xattrs",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661840,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583206917,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:392",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_read_protected_xattrs",
        "security/integrity/evm/evm_main.c:evm_read_protected_xattrs",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202048,
      "name": "__vfs_getxattr",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780544,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:413",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_read_protected_xattrs",
        "security/integrity/evm/evm_main.c:evm_read_protected_xattrs",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780544,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583997232,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:411",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_read_protected_xattrs",
        "security/integrity/evm/evm_main.c:evm_read_protected_xattrs",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997232,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584209872,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:411",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_file_xattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_read_protected_xattrs",
        "security/integrity/evm/evm_main.c:evm_read_protected_xattrs",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209872,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493553424,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493553424,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227102260,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227102260,
      "name": "__vfs_getxattr",
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287124704,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287124704,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273213848,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273213848,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997920,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997920,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935488,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935488,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989200,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989200,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "__vfs_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059664,
      "name": "__vfs_getxattr",
      "external": true,
      "loc": "fs/xattr.c:303",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr",
        "fs/ecryptfs/inode.c:ecryptfs_getxattr_lower",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_need_killpriv",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:inode_doinit_use_xattr",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059664,
      "name": "__vfs_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
ssize_t __vfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
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

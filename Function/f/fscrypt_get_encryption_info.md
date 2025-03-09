# Function: <code>fscrypt_get_encryption_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509808,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keyinfo.c:292",
      "file": "fs/crypto/keyinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509808,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581593968,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keyinfo.c:173",
      "file": "fs/crypto/keyinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593968,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1091
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581653936,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keyinfo.c:251",
      "file": "fs/crypto/keyinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653936,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1364
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581798528,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keyinfo.c:242",
      "file": "fs/crypto/keyinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798528,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581974432,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keyinfo.c:288",
      "file": "fs/crypto/keyinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973104,
      "name": "fscrypt_get_encryption_info.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1325
    },
    {
      "addr": 18446744071581974560,
      "name": "fscrypt_get_encryption_info.part.7.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071581974432,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582062528,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keyinfo.c:504",
      "file": "fs/crypto/keyinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061056,
      "name": "fscrypt_get_encryption_info.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1469
    },
    {
      "addr": 18446744071582062763,
      "name": "fscrypt_get_encryption_info.part.11.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071582062528,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582223536,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keyinfo.c:502",
      "file": "fs/crypto/keyinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222112,
      "name": "fscrypt_get_encryption_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1420
    },
    {
      "addr": 18446744071582223774,
      "name": "fscrypt_get_encryption_info.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071582223536,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:421",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310543,
      "name": "fscrypt_get_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071582309056,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1241
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:430",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:fscrypt_prepare_setflags",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597078,
      "name": "fscrypt_get_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071582595648,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1070
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
int fscrypt_get_encryption_info(struct inode * inode, bool allow_unsupported)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:564",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:fscrypt_prepare_setflags",
        "fs/crypto/hooks.c:__fscrypt_prepare_readdir",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591342014,
      "name": "fscrypt_get_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071582667696,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int fscrypt_get_encryption_info(struct inode * inode, bool allow_unsupported)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:588",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:fscrypt_prepare_setflags",
        "fs/crypto/hooks.c:__fscrypt_prepare_readdir",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591284759,
      "name": "fscrypt_get_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071582696592,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int fscrypt_get_encryption_info(struct inode * inode, bool allow_unsupported)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:621",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:fscrypt_prepare_setflags",
        "fs/crypto/hooks.c:__fscrypt_prepare_readdir",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592240880,
      "name": "fscrypt_get_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583022592,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int fscrypt_get_encryption_info(struct inode * inode, bool allow_unsupported)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:608",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:fscrypt_prepare_setflags",
        "fs/crypto/hooks.c:__fscrypt_prepare_readdir",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594019662,
      "name": "fscrypt_get_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583494592,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int fscrypt_get_encryption_info(struct inode * inode, bool allow_unsupported)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090304,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:617",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:fscrypt_prepare_setflags",
        "fs/crypto/hooks.c:__fscrypt_prepare_readdir",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090304,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int fscrypt_get_encryption_info(struct inode * inode, bool allow_unsupported)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317264,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:636",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:fscrypt_prepare_setflags",
        "fs/crypto/hooks.c:__fscrypt_prepare_readdir",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317264,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int fscrypt_get_encryption_info(struct inode * inode, bool allow_unsupported)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534688,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:643",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:fscrypt_prepare_setflags",
        "fs/crypto/hooks.c:__fscrypt_prepare_readdir",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit",
        "fs/crypto/policy.c:fscrypt_has_permitted_context",
        "fs/crypto/policy.c:fscrypt_has_permitted_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534688,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493886944,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:421",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493886944,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1424
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227367676,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:421",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227367676,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1488
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287522480,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:421",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287522480,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1828
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273447850,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:421",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273447850,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1136
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:421",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279279,
      "name": "fscrypt_get_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071582277792,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1241
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:421",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217039,
      "name": "fscrypt_get_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071582215552,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1241
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:421",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269759,
      "name": "fscrypt_get_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071582268272,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1241
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
int fscrypt_get_encryption_info(struct inode * inode)
```

```json
{
  "name": "fscrypt_get_encryption_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_encryption_info",
      "external": true,
      "loc": "fs/crypto/keysetup.c:421",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_prepare_link",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348317,
      "name": "fscrypt_get_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071582346832,
      "name": "fscrypt_get_encryption_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int fscrypt_get_encryption_info(struct inode * inode)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool allow_unsupported</code>
</li>
</ul>
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

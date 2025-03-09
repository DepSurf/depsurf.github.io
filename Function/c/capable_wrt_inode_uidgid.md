# Function: <code>capable_wrt_inode_uidgid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411296,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:442",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:inode_change_ok",
        "fs/attr.c:inode_change_ok",
        "fs/attr.c:inode_change_ok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411296,
      "name": "capable_wrt_inode_uidgid",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423488,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:468",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:should_remove_suid",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:inode_change_ok",
        "fs/attr.c:inode_change_ok",
        "fs/attr.c:inode_change_ok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423488,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579445040,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:482",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:should_remove_suid",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445040,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433072,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:482",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:should_remove_suid",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433072,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461424,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:483",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:should_remove_suid",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461424,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475008,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:483",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475008,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508688,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:485",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508688,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527680,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527680,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553760,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553760,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584592,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584592,
      "name": "capable_wrt_inode_uidgid",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564624,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564624,
      "name": "capable_wrt_inode_uidgid",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool capable_wrt_inode_uidgid(struct user_namespace * mnt_userns, const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:504",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/fuse/acl.c:fuse_set_acl",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591221980,
      "name": "capable_wrt_inode_uidgid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071579570720,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool capable_wrt_inode_uidgid(struct user_namespace * mnt_userns, const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:504",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/fuse/acl.c:fuse_set_acl",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592101315,
      "name": "capable_wrt_inode_uidgid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071579644640,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool capable_wrt_inode_uidgid(struct user_namespace * mnt_userns, const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:505",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__check_sticky",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/fuse/acl.c:fuse_set_acl",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593868870,
      "name": "capable_wrt_inode_uidgid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071579740192,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
bool capable_wrt_inode_uidgid(struct user_namespace * mnt_userns, const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871472,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:505",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__check_sticky",
        "fs/inode.c:mode_strip_sgid",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/fuse/acl.c:fuse_set_acl",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871472,
      "name": "capable_wrt_inode_uidgid",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(struct mnt_idmap * idmap, const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920688,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:493",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__check_sticky",
        "fs/inode.c:mode_strip_sgid",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/fuse/acl.c:fuse_set_acl",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920688,
      "name": "capable_wrt_inode_uidgid",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(struct mnt_idmap * idmap, const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959936,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:493",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__check_sticky",
        "fs/inode.c:mode_strip_sgid",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/fuse/acl.c:fuse_set_acl",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959936,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490706976,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490706976,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224769820,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224769820,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283530752,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283530752,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271431058,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271431058,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530064,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530064,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458864,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458864,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527344,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527344,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool capable_wrt_inode_uidgid(const struct inode * inode, int cap)
```

```json
{
  "name": "capable_wrt_inode_uidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560416,
      "name": "capable_wrt_inode_uidgid",
      "external": true,
      "loc": "kernel/capability.c:502",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "security/commoncap.c:cap_inode_removexattr",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560416,
      "name": "capable_wrt_inode_uidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<code>inode, cap</code> ➡️ <code>mnt_userns, inode, cap</code>
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

# Function: <code>__ext4_new_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581549104,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:742",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549104,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5042
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581734848,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:742",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734848,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5231
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822448,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:742",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822448,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5162
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946032,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:743",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946032,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5374
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582095360,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:772",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095360,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5085
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582283184,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:742",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283184,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5553
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381920,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:742",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381920,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5553
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582550288,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:742",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582550288,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5382
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582651072,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:740",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582651072,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5502
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582963008,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:755",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_whiteout_for_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582963008,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4914
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583038688,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:922",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_whiteout_for_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583038688,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4863
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
struct inode * __ext4_new_inode(struct user_namespace * mnt_userns, handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583064192,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:923",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583064192,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5266
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
struct inode * __ext4_new_inode(struct user_namespace * mnt_userns, handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:925",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592256309,
      "name": "__ext4_new_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071583402208,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5339
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
struct inode * __ext4_new_inode(struct user_namespace * mnt_userns, handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:925",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594037354,
      "name": "__ext4_new_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071583917232,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5546
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct inode * __ext4_new_inode(struct user_namespace * mnt_userns, handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:924",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596070453,
      "name": "__ext4_new_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071584543360,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5439
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct inode * __ext4_new_inode(struct mnt_idmap * idmap, handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:923",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596593979,
      "name": "__ext4_new_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071584772272,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct inode * __ext4_new_inode(struct mnt_idmap * idmap, handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:923",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597499521,
      "name": "__ext4_new_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585005360,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5167
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494304080,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:740",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494304080,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4884
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227738388,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:740",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227738388,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 6040
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288021696,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:740",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288021696,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 6604
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273745278,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:740",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273745278,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4792
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619808,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:740",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619808,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5502
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556976,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:740",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556976,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5502
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609664,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:740",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609664,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5502
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
struct inode * __ext4_new_inode(handle_t * handle, struct inode * dir, umode_t mode, const struct qstr * qstr, __u32 goal, uid_t * owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks)
```

```json
{
  "name": "__ext4_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582692384,
      "name": "__ext4_new_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:740",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582692384,
      "name": "__ext4_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5749
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__u32 i_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>handle, dir, mode, qstr, goal, owner, handle_type, line_no, nblocks</code> ➡️ <code>handle, dir, mode, qstr, goal, owner, i_flags, handle_type, line_no, nblocks</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>handle, dir, mode, qstr, goal, owner, i_flags, handle_type, line_no, nblocks</code> ➡️ <code>mnt_userns, handle, dir, mode, qstr, goal, owner, i_flags, handle_type, line_no, nblocks</code>
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

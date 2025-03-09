# Function: <code>__audit_inode_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __audit_inode_child(const struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056848,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:1851",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_delete",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056848,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090096,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:1850",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090096,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130400,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:1855",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130400,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580136080,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:1864",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136080,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 887
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580188528,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:1864",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188528,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1020
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:1871",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256018,
      "name": "__audit_inode_child.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071580248432,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:1857",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309249,
      "name": "__audit_inode_child.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071580296608,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2061",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361313,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580345328,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2061",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410129,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580394096,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2092",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580489020,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580479792,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 962
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2109",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315907,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580468128,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2106",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591258089,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580471280,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 965
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2119",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592162764,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580638368,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 965
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2410",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593935924,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071580849264,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135856,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2388",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135856,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1042
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224768,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2385",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224768,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1124
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581331104,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2380",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/event_inode.c:eventfs_create_events_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331104,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1123
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491660184,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2061",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491660184,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225614272,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2061",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225614272,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284675040,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2061",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284675040,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1720
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272052734,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2061",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272052734,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2061",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378929,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580362896,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2061",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326097,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580310064,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2061",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580370177,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580354144,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
void __audit_inode_child(struct inode * parent, const struct dentry * dentry, const unsigned char type)
```

```json
{
  "name": "__audit_inode_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode_child",
      "external": true,
      "loc": "kernel/auditsc.c:2061",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425697,
      "name": "__audit_inode_child.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580409440,
      "name": "__audit_inode_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 945
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct inode * parent</code> ➡️ <code>struct inode * parent</code>
</li>
</ul>
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

# Function: <code>inode_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582263521,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1635",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:file_has_perm",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_setotherxattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582504190,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1706",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setotherxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582596936,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1714",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setotherxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665280,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1703",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setotherxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665280,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582820000,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1707",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582820000,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583019952,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1808",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583019952,
      "name": "inode_has_perm.isra.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583127936,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1622",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127936,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583314864,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1666",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314864,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420160,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1668",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420160,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583760816,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1621",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583760816,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881408,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1630",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881408,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583907520,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1689",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583907520,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584271232,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1681",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584271232,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584886544,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1619",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584886544,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585593296,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1618",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_remove_acl",
        "security/selinux/hooks.c:selinux_inode_get_acl",
        "security/selinux/hooks.c:selinux_inode_set_acl",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585593296,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585824080,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1630",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_remove_acl",
        "security/selinux/hooks.c:selinux_inode_get_acl",
        "security/selinux/hooks.c:selinux_inode_set_acl",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824080,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586072496,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1672",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_remove_acl",
        "security/selinux/hooks.c:selinux_inode_get_acl",
        "security/selinux/hooks.c:selinux_inode_set_acl",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072496,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495176744,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1668",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495176744,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228563904,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1668",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228563904,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289115600,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1668",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289115600,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274418078,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1668",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274418078,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388896,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1668",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388896,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583325984,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1668",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325984,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583372672,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1668",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372672,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```

```json
{
  "name": "inode_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583467056,
      "name": "inode_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1668",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_mmap_file",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:file_has_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583467056,
      "name": "inode_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int inode_has_perm(const struct cred * cred, struct inode * inode, u32 perms, struct common_audit_data * adp)
```
</details>
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

# Function: <code>__audit_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060208,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1753",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_mountpoint",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060208,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 789
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580093376,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1752",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093376,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133680,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1757",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133680,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580139376,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1766",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139376,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191984,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1766",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191984,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1773",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256080,
      "name": "__audit_inode.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580251840,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 694
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1759",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309311,
      "name": "__audit_inode.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580305088,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 694
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1944",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361376,
      "name": "__audit_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580357424,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 807
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1944",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410192,
      "name": "__audit_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580406192,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 807
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580484880,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1975",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_tmpfile",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:pick_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484880,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580473136,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1992",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_tmpfile",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:pick_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580473136,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1989",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:pick_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591258152,
      "name": "__audit_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580476784,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:2002",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:pick_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592162970,
      "name": "__audit_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580644224,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:2293",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:pick_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593936007,
      "name": "__audit_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580852448,
      "name": "__audit_inode",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139648,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:2271",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:pick_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139648,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1021
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581232560,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:2268",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:__filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:pick_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581232560,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338720,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:2263",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:__filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:pick_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338720,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1083
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491671576,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1944",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__arm64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491671576,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225625836,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1944",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:__se_sys_mq_open",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225625836,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284680032,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1944",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284680032,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1544
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272062474,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1944",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:__se_sys_mq_open",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272062474,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1944",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378992,
      "name": "__audit_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580374992,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 807
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1944",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326160,
      "name": "__audit_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580322160,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 807
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1944",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580370240,
      "name": "__audit_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580366240,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 807
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
void __audit_inode(struct filename * name, const struct dentry * dentry, unsigned int flags)
```

```json
{
  "name": "__audit_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_inode",
      "external": true,
      "loc": "kernel/auditsc.c:1944",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_file",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:trailing_symlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425760,
      "name": "__audit_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580421632,
      "name": "__audit_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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

# Function: <code>fsnotify_add_mark_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, struct fsnotify_group * group, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581272064,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:336",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581272064,
      "name": "fsnotify_add_mark_locked",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, struct fsnotify_group * group, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581437584,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:358",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437584,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, struct fsnotify_group * group, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518528,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:358",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518528,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571824,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:571",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571824,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 749
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716128,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:568",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716128,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883088,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:574",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883088,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968096,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:609",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968096,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 731
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101712,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:636",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101712,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:636",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180098,
      "name": "fsnotify_add_mark_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071582178496,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582416320,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:640",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582416320,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470448,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:640",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470448,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497504,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:638",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497504,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812384,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:667",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812384,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int obj_type, int add_flags, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367040,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:704",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367040,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int obj_type, int add_flags, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583951120,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:704",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951120,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int obj_type, int add_flags, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584174416,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:704",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174416,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int obj_type, int add_flags)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584388400,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:669",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388400,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493737056,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:636",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493737056,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227261176,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:636",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227261176,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287346624,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:636",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287346624,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273345760,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:636",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273345760,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:636",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148834,
      "name": "fsnotify_add_mark_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071582147232,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:636",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086274,
      "name": "fsnotify_add_mark_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071582084672,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:636",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139314,
      "name": "fsnotify_add_mark_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071582137712,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
int fsnotify_add_mark_locked(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_locked",
      "external": true,
      "loc": "fs/notify/mark.c:636",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/mark.c:fsnotify_add_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212388,
      "name": "fsnotify_add_mark_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582210720,
      "name": "fsnotify_add_mark_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 971
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
<b>Param removed. </b>
<code>struct fsnotify_group * group</code>
</li>
<li>
<b>Param reordered. </b>
<code>mark, group, inode, mnt, allow_dups</code> ➡️ <code>mark, inode, mnt, allow_dups</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>fsnotify_connp_t * connp</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int type</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vfsmount * mnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__kernel_fsid_t * fsid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int obj_type</code>
</li>
<li>
<b>Param added. </b>
<code>int add_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int type</code>
</li>
<li>
<b>Param removed. </b>
<code>int allow_dups</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__kernel_fsid_t * fsid</code>
</li>
</ul>
</details>
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

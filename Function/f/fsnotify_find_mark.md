# Function: <code>fsnotify_find_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_mark(struct hlist_head * head, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581272624,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:413",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inode_mark.c:fsnotify_find_inode_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_find_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581272624,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct fsnotify_mark * fsnotify_find_mark(struct hlist_head * head, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438144,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:436",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inode_mark.c:fsnotify_find_inode_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_find_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438144,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct fsnotify_mark * fsnotify_find_mark(struct hlist_head * head, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519088,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:436",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inode_mark.c:fsnotify_find_inode_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_find_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519088,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct fsnotify_mark * fsnotify_find_mark(struct fsnotify_mark_connector * * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572672,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:630",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572672,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct fsnotify_mark * fsnotify_find_mark(struct fsnotify_mark_connector * * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717008,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:629",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717008,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct fsnotify_mark * fsnotify_find_mark(struct fsnotify_mark_connector * * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883952,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:635",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883952,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968928,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:669",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968928,
      "name": "fsnotify_find_mark",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102096,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102096,
      "name": "fsnotify_find_mark",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177472,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177472,
      "name": "fsnotify_find_mark",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415280,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:700",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_chunk",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415280,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582469392,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:700",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_chunk",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469392,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582496464,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_chunk",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582496464,
      "name": "fsnotify_find_mark",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582811264,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:725",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_chunk",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582811264,
      "name": "fsnotify_find_mark",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365664,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:762",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_chunk",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365664,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583949600,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:762",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_chunk",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949600,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172880,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:762",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_chunk",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172880,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584386864,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:726",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_chunk",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386864,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493735496,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493735496,
      "name": "fsnotify_find_mark",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227259820,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227259820,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287343120,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287343120,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273343502,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273343502,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146208,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146208,
      "name": "fsnotify_find_mark",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083648,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083648,
      "name": "fsnotify_find_mark",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582136688,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136688,
      "name": "fsnotify_find_mark",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_mark(fsnotify_connp_t * connp, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_find_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209712,
      "name": "fsnotify_find_mark",
      "external": true,
      "loc": "fs/notify/mark.c:696",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209712,
      "name": "fsnotify_find_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<code>struct fsnotify_mark_connector * * connp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hlist_head * head</code>
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
<b>Param type changed. </b>
<code>struct fsnotify_mark_connector * * connp</code> ➡️ <code>fsnotify_connp_t * connp</code>
</li>
</ul>
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

# Function: <code>fsnotify_recalc_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 fsnotify_recalc_mask(struct hlist_head * head)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271040,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:115",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inode_mark.c:fsnotify_recalc_inode_mask",
        "fs/notify/inode_mark.c:fsnotify_destroy_inode_mark",
        "fs/notify/inode_mark.c:fsnotify_add_inode_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_recalc_vfsmount_mask",
        "fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271040,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
u32 fsnotify_recalc_mask(struct hlist_head * head)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581436656,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:119",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inode_mark.c:fsnotify_add_inode_mark",
        "fs/notify/inode_mark.c:fsnotify_destroy_inode_mark",
        "fs/notify/inode_mark.c:fsnotify_recalc_inode_mask",
        "fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_recalc_vfsmount_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436656,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
u32 fsnotify_recalc_mask(struct hlist_head * head)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517600,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:119",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inode_mark.c:fsnotify_add_inode_mark",
        "fs/notify/inode_mark.c:fsnotify_destroy_inode_mark",
        "fs/notify/inode_mark.c:fsnotify_recalc_inode_mask",
        "fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_recalc_vfsmount_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517600,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581572349,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:145",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
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
      "addr": 18446744071581570944,
      "name": "fsnotify_recalc_mask.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071581571040,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581716653,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:135",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
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
      "addr": 18446744071581715456,
      "name": "fsnotify_recalc_mask.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071581715552,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581883647,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:134",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
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
      "addr": 18446744071581881216,
      "name": "fsnotify_recalc_mask.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071581882320,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581967248,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:153",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967248,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582100880,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100880,
      "name": "fsnotify_recalc_mask",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582177664,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177664,
      "name": "fsnotify_recalc_mask",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582416511,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415472,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582470639,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469616,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582497691,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582496688,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582812571,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/dnotify/dnotify.c:dnotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582811488,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583367216,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:185",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/dnotify/dnotify.c:dnotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365920,
      "name": "fsnotify_recalc_mask",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583951296,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:185",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/dnotify/dnotify.c:dnotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949888,
      "name": "fsnotify_recalc_mask",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584174592,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:185",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/dnotify/dnotify.c:dnotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173168,
      "name": "fsnotify_recalc_mask",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584388570,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:185",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/dnotify/dnotify.c:dnotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387152,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493735776,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493735776,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227260112,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227260112,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287344944,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/dnotify/dnotify.c:dnotify_recalc_inode_mask",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287344944,
      "name": "fsnotify_recalc_mask",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273344502,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273344502,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582146400,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146400,
      "name": "fsnotify_recalc_mask",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582083840,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083840,
      "name": "fsnotify_recalc_mask",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582136880,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136880,
      "name": "fsnotify_recalc_mask",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_recalc_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582209904,
      "name": "fsnotify_recalc_mask",
      "external": true,
      "loc": "fs/notify/mark.c:141",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209904,
      "name": "fsnotify_recalc_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
<code>struct fsnotify_mark_connector * conn</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hlist_head * head</code>
</li>
<li>
<b>Return type changed. </b>
<code>u32</code> ➡️ <code>void</code>
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

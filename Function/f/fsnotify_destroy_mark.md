# Function: <code>fsnotify_destroy_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271488,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:204",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271488,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581436928,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:226",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436928,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517872,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:226",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517872,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571696,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:391",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571696,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716000,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:388",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716000,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882944,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:395",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882944,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967952,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:439",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967952,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101568,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:426",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101568,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582178352,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:426",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178352,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582417188,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:430",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582416192,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582471316,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:430",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470320,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582498356,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:428",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497376,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582813252,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:452",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812256,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583368202,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:493",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583366800,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583952330,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:493",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950848,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584175626,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:493",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174128,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584389578,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:493",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388112,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493736848,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:426",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493736848,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227260992,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:426",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227260992,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287346400,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:426",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287346400,
      "name": "fsnotify_destroy_mark",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273345568,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:426",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273345568,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147088,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:426",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147088,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582084528,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:426",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084528,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137568,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:426",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137568,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fsnotify_destroy_mark(struct fsnotify_mark * mark, struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_destroy_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210576,
      "name": "fsnotify_destroy_mark",
      "external": true,
      "loc": "fs/notify/mark.c:426",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_watch_handle_event",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210576,
      "name": "fsnotify_destroy_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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

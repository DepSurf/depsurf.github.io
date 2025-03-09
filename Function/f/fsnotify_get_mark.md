# Function: <code>fsnotify_get_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581271024,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:99",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271024,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581438556,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:103",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_detach_group_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436640,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581519494,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:103",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_detach_group_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517584,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571008,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:106",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571008,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715520,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:106",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715520,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882288,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:106",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882288,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967152,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:106",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967152,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582100784,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100784,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177440,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177440,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415200,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415200,
      "name": "fsnotify_get_mark",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582469312,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469312,
      "name": "fsnotify_get_mark",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582496384,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582496384,
      "name": "fsnotify_get_mark",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582811184,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582811184,
      "name": "fsnotify_get_mark",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365536,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365536,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583949456,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949456,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172736,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172736,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584386720,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386720,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493735416,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493735416,
      "name": "fsnotify_get_mark",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227259720,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227259720,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287348012,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287344752,
      "name": "fsnotify_get_mark",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273346600,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273344344,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146176,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146176,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083616,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083616,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582136656,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136656,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fsnotify_get_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209680,
      "name": "fsnotify_get_mark",
      "external": true,
      "loc": "fs/notify/mark.c:94",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_find_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209680,
      "name": "fsnotify_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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

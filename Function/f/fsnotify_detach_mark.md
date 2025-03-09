# Function: <code>fsnotify_detach_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271088,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:131",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271088,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581436720,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:135",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_detach_group_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436720,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517664,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:135",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_detach_group_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517664,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571440,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:336",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571440,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715744,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:333",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715744,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882688,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:340",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882688,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967696,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:384",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967696,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101296,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:371",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101296,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582178080,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:371",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178080,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415920,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:375",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415920,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470048,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:375",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470048,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497120,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:375",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497120,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812000,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:399",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812000,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583366480,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:442",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583366480,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583950496,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:442",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950496,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584173776,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:442",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173776,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387760,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:442",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387760,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493736376,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:371",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493736376,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227260608,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:371",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227260608,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287345776,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:371",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287345776,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273345092,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:371",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273345092,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146816,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:371",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146816,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582084256,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:371",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084256,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137296,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:371",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137296,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void fsnotify_detach_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_detach_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210320,
      "name": "fsnotify_detach_mark",
      "external": true,
      "loc": "fs/notify/mark.c:371",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_destroy_mark",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210320,
      "name": "fsnotify_detach_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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

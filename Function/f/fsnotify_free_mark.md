# Function: <code>fsnotify_free_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271296,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:177",
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
      "addr": 18446744071581271296,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581438448,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:218",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags",
        "fs/notify/mark.c:fsnotify_destroy_mark"
      ],
      "caller_func": [
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
      "addr": 18446744071581436592,
      "name": "fsnotify_free_mark.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071581437008,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581519386,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:218",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags",
        "fs/notify/mark.c:fsnotify_destroy_mark"
      ],
      "caller_func": [
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
      "addr": 18446744071581517536,
      "name": "fsnotify_free_mark.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071581517952,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581571584,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:369",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071581571584,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581715888,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:366",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071581715888,
      "name": "fsnotify_free_mark",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882832,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:373",
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
      "addr": 18446744071581882832,
      "name": "fsnotify_free_mark",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967840,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:417",
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
      "addr": 18446744071581967840,
      "name": "fsnotify_free_mark",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101456,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:404",
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
      "addr": 18446744071582101456,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582178240,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:404",
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
      "addr": 18446744071582178240,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582416080,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:408",
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
      "addr": 18446744071582416080,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470208,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:408",
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
      "addr": 18446744071582470208,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497264,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:406",
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
      "addr": 18446744071582497264,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812144,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:430",
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
      "addr": 18446744071582812144,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583366672,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:471",
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
      "addr": 18446744071583366672,
      "name": "fsnotify_free_mark",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583950704,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:471",
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
      "addr": 18446744071583950704,
      "name": "fsnotify_free_mark",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584173984,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:471",
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
      "addr": 18446744071584173984,
      "name": "fsnotify_free_mark",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387968,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:471",
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
      "addr": 18446744071584387968,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493736648,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:404",
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
      "addr": 18446603336493736648,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227260852,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:404",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
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
      "addr": 3227260852,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287346112,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:404",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
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
      "addr": 13835058055287346112,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273345350,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:404",
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
      "addr": 18446743936273345350,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146976,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:404",
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
      "addr": 18446744071582146976,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582084416,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:404",
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
      "addr": 18446744071582084416,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137456,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:404",
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
      "addr": 18446744071582137456,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void fsnotify_free_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_free_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210464,
      "name": "fsnotify_free_mark",
      "external": true,
      "loc": "fs/notify/mark.c:404",
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
      "addr": 18446744071582210464,
      "name": "fsnotify_free_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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

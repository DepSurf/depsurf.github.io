# Function: <code>fsnotify_put_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581270656,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:104",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_mark_destroy",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270656,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581436544,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:108",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_mark_destroy_list",
        "fs/notify/mark.c:fsnotify_detach_group_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436544,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581517488,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:108",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_mark_destroy_list",
        "fs/notify/mark.c:fsnotify_detach_group_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group_flags",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517488,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581570576,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:207",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_finish_user_wait",
        "fs/notify/mark.c:fsnotify_finish_user_wait",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570576,
      "name": "fsnotify_put_mark",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714816,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:197",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_get_mark_safe",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714816,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581881632,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:196",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881632,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581966672,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:239",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966672,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582100304,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100304,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176960,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176960,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582414688,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_to_parent",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582414688,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468800,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_to_parent",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468800,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582495872,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582495872,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582810560,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:251",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582810560,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583363872,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:293",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363872,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947664,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:293",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947664,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584170864,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:293",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170864,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584385088,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:293",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385088,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493734720,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493734720,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227257892,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227257892,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287341696,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287341696,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273343746,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273343746,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145696,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145696,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083136,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083136,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582136176,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136176,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void fsnotify_put_mark(struct fsnotify_mark * mark)
```

```json
{
  "name": "fsnotify_put_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209056,
      "name": "fsnotify_put_mark",
      "external": true,
      "loc": "fs/notify/mark.c:227",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_remove_watch_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_remove_watch",
        "kernel/audit_fsnotify.c:audit_remove_mark_rule",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_clear_marks_by_group",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209056,
      "name": "fsnotify_put_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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

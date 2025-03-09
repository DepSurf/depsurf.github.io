# Function: <code>namespace_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121600,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1339",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121600,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287344,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1339",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287344,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366208,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1413",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366208,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581421184,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1355",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581421184,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581562688,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1420",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562688,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718832,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1446",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718832,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581806032,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1358",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806032,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930512,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1366",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930512,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003136,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1366",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003136,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582239360,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1416",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239360,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582288192,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1419",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582288192,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313744,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1430",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313744,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582633392,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1439",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633392,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583169792,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1480",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169792,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583744528,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1585",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583744528,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583961056,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1559",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961056,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584174256,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1556",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174256,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493523864,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1366",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493523864,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227076296,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1366",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227076296,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287089616,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1366",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287089616,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273191020,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1366",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273191020,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581971872,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1366",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971872,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909440,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1366",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909440,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581963152,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1366",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963152,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void namespace_unlock()
```

```json
{
  "name": "namespace_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033584,
      "name": "namespace_unlock",
      "external": false,
      "loc": "fs/namespace.c:1366",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mnt_set_expiry",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:collect_mounts",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033584,
      "name": "namespace_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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

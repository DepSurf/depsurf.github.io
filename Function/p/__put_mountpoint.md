# Function: <code>__put_mountpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581926672,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:755",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926672,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581999280,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:755",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999280,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582255606,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:771",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233248,
      "name": "__put_mountpoint.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071582233392,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582304902,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:771",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282048,
      "name": "__put_mountpoint.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071582282192,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582332500,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:785",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308592,
      "name": "__put_mountpoint.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071582308736,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582653092,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:787",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582628032,
      "name": "__put_mountpoint.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071582628176,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583192231,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:830",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159920,
      "name": "__put_mountpoint.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071583160080,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583767591,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:941",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734368,
      "name": "__put_mountpoint.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071583734544,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583984758,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:850",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951168,
      "name": "__put_mountpoint.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071583951344,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584197302,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:838",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159088,
      "name": "__put_mountpoint.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071584159264,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493519808,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:755",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493519808,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227093084,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:755",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:umount_mnt"
      ],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:umount_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227071436,
      "name": "__put_mountpoint.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287112536,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:755",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:umount_mnt"
      ],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:umount_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287080304,
      "name": "__put_mountpoint.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273187848,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:755",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273187848,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581968016,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:755",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968016,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581905584,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:755",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905584,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581959296,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:755",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959296,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```

```json
{
  "name": "__put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582030272,
      "name": "__put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:755",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030272,
      "name": "__put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __put_mountpoint(struct mountpoint * mp, struct list_head * list)
```
</details>
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

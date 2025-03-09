# Function: <code>kernfs_rename_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581511408,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1431",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rename",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511408,
      "name": "kernfs_rename_ns",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697040,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1480",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697040,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785008,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1431",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785008,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839792,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1441",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839792,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989536,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1506",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989536,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177104,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177104,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272240,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272240,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436624,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436624,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582535360,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535360,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582841328,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1533",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582841328,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582914080,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1532",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582914080,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582941776,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1534",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582941776,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583276944,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1561",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276944,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583781152,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1606",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583781152,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584399776,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1683",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584399776,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584628320,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1690",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584628320,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584860480,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1706",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584860480,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494169808,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494169808,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227609604,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227609604,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287854304,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287854304,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273638362,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273638362,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504096,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504096,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441312,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441312,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582494576,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494576,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
int kernfs_rename_ns(struct kernfs_node * kn, struct kernfs_node * new_parent, const char * new_name, const void * new_ns)
```

```json
{
  "name": "kernfs_rename_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582575216,
      "name": "kernfs_rename_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_move_dir_ns",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582575216,
      "name": "kernfs_rename_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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

# Function: <code>umount_tree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581122432,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1399",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122432,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288176,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1399",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288176,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581367344,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1473",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581367344,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422176,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1415",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422176,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581563680,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1480",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563680,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581720944,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1506",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581720944,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581807744,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1418",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807744,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926832,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1435",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926832,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999440,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1435",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999440,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582233424,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1485",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:shrink_submounts",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233424,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582282224,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1488",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:shrink_submounts",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282224,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582308768,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1499",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308768,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582628208,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1508",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582628208,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583162960,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1549",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583162960,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583738064,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1654",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738064,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954896,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1628",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954896,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584163600,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1625",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163600,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493520048,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1435",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493520048,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227071648,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1435",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227071648,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287082752,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1435",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287082752,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273188044,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1435",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273188044,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968176,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1435",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968176,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581905744,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1435",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905744,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581959456,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1435",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959456,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
void umount_tree(struct mount * mnt, enum umount_tree_flags how)
```

```json
{
  "name": "umount_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582030432,
      "name": "umount_tree",
      "external": false,
      "loc": "fs/namespace.c:1435",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030432,
      "name": "umount_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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

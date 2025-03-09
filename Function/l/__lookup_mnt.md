# Function: <code>__lookup_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581128928,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:630",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namei.c:lookup_fast",
        "fs/namespace.c:__lookup_mnt_last",
        "fs/namespace.c:lookup_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128928,
      "name": "__lookup_mnt",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581294800,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:630",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:lookup_mnt",
        "fs/namespace.c:__lookup_mnt_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294800,
      "name": "__lookup_mnt",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373632,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:629",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373632,
      "name": "__lookup_mnt",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581428816,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:630",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428816,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570704,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:690",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570704,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581726016,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:700",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726016,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812560,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:612",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812560,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932656,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932656,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005280,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005280,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582242304,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__follow_mount_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582242304,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582291296,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__follow_mount_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291296,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318400,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:623",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:step_into",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318400,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:625",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:step_into",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592230812,
      "name": "__lookup_mnt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071582638816,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:668",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:step_into",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594010780,
      "name": "__lookup_mnt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583175760,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:779",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:step_into",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596051613,
      "name": "__lookup_mnt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583750496,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:688",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:step_into",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596574143,
      "name": "__lookup_mnt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583967040,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:695",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:step_into",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597478681,
      "name": "__lookup_mnt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584179504,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493526512,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493526512,
      "name": "__lookup_mnt",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227079892,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namei.c:__follow_mount_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227079892,
      "name": "__lookup_mnt",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287092992,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287092992,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273193556,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273193556,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974016,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974016,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911584,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911584,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581965296,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965296,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct mount * __lookup_mnt(struct vfsmount * mnt, struct dentry * dentry)
```

```json
{
  "name": "__lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035744,
      "name": "__lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:609",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot_rcu",
        "fs/dcache.c:path_check_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:lookup_mnt",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_mount_unlock",
        "fs/pnode.c:propagate_mount_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035744,
      "name": "__lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
